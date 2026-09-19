<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtpj9ebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mtpj9ebze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:japanese-symbol-for-beginner" {...props}></Icon>
