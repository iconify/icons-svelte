<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6x2qsxjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6x2qsxjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:keyboard-music" {...props}></Icon>
