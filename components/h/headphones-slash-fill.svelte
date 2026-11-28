<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cttyy7b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cttyy7b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:headphones-slash-fill" {...props}></Icon>
