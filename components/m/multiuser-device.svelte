<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3enxxbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z3enxxbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:multiuser-device" {...props}></Icon>
