<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-5-fgb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-5-fgb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nixos-dark" {...props}></Icon>
