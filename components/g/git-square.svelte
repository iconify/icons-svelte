<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcc10c5ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kcc10c5ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:git-square" {...props}></Icon>
