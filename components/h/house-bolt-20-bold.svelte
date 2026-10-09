<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coivkzecr.css';
import '../../css/e/ed9sx_fzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="ed9sx_fzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-bolt-20-bold" {...props}></Icon>
