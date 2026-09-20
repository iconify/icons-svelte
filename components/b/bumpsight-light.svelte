<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9cc-xor.css';
import '../../css/r/rd8e13qsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="eo9cc-xor"/><path class="rd8e13qsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bumpsight-light" {...props}></Icon>
