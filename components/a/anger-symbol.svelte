<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0c0obwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="us0c0obwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:anger-symbol" {...props}></Icon>
