<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrkzq_4jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nrkzq_4jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-yy" {...props}></Icon>
