<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyqka1bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uyqka1bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:accessibility" {...props}></Icon>
