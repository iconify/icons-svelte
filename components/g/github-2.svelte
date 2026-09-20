<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi8f3ubar.css';
import '../../css/u/u69h-uyii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8f3ubar"/><path class="u69h-uyii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:github-2" {...props}></Icon>
