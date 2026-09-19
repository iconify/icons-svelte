<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr12701qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mr12701qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pile-of-poo" {...props}></Icon>
