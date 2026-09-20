<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4k57gbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4k57gbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-8-1" {...props}></Icon>
