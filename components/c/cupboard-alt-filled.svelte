<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpdsybbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpdsybbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cupboard-alt-filled" {...props}></Icon>
