<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7f57udbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7f57udbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiodeck-light" {...props}></Icon>
