<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4u48l9nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4u48l9nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:leaf" {...props}></Icon>
