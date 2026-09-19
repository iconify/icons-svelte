<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctx78_e8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ctx78_e8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hammer-and-pick" {...props}></Icon>
