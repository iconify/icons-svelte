<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c60-6kb4c.css';
import '../../css/z/ziz-v20vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c60-6kb4c"/><path class="ziz-v20vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qwik-dark" {...props}></Icon>
