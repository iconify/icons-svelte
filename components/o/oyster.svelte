<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i631qty3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i631qty3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:oyster" {...props}></Icon>
