<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqv5m4zzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nqv5m4zzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bookmark-solid" {...props}></Icon>
