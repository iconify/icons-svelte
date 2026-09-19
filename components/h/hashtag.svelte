<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpjqrc5ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xpjqrc5ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hashtag" {...props}></Icon>
