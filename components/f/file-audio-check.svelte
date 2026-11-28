<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu2n5ibht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2n5ibht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-audio-check" {...props}></Icon>
