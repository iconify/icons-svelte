<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t53h6xtlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t53h6xtlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reflect-vertical" {...props}></Icon>
