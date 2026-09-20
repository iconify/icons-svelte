<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfukdybcj.css';
import '../../css/e/e-3mmc50d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zfukdybcj"/><path class="e-3mmc50d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:curly-loop" {...props}></Icon>
