<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeb6jzb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeb6jzb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fog-filled" {...props}></Icon>
