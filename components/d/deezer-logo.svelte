<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od-418bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od-418bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deezer-logo" {...props}></Icon>
