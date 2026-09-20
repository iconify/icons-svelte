<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzq33dbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzq33dbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-down-right-alt" {...props}></Icon>
