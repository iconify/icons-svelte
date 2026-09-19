<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prax3ibas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="prax3ibas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:kite" {...props}></Icon>
