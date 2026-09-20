<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p484ajszk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p484ajszk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-simple-destination" {...props}></Icon>
