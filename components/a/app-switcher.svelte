<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgu8nmfrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wgu8nmfrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:app-switcher" {...props}></Icon>
