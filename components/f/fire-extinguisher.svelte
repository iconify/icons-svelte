<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrpor5pjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrpor5pjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:fire-extinguisher" {...props}></Icon>
