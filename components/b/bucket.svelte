<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caintxonb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="caintxonb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:bucket" {...props}></Icon>
