<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk52tmsyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dk52tmsyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bed" {...props}></Icon>
