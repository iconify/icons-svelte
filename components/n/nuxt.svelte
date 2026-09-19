<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esbpl1bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="esbpl1bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nuxt" {...props}></Icon>
