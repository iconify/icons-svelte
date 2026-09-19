<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en29hfbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en29hfbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-circle" {...props}></Icon>
