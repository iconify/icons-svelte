<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2oxn1iue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w2oxn1iue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:love-you-gesture" {...props}></Icon>
