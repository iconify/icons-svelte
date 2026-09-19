<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae3ks5tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gae3ks5tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-large-square" {...props}></Icon>
