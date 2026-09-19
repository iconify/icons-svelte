<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duliw2bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":644};
const content = `<path class="duliw2bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:alignleft" {...props}></Icon>
