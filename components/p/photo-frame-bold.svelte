<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpnkdflmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpnkdflmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:photo-frame-bold" {...props}></Icon>
