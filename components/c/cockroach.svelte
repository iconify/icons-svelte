<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb8f1_oar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lb8f1_oar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cockroach" {...props}></Icon>
