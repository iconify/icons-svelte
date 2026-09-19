<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0ole3zzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f0ole3zzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array-strings" {...props}></Icon>
