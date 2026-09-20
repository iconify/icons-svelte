<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzqzttbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzqzttbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-bar-down" {...props}></Icon>
