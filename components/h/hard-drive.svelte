<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pld43v02m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pld43v02m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:hard-drive" {...props}></Icon>
