<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1a7lqbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a1a7lqbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:index-close" {...props}></Icon>
