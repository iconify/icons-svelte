<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfe9tcbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wfe9tcbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:8-circle" {...props}></Icon>
