<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztoqbfbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ztoqbfbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-two-ltr" {...props}></Icon>
