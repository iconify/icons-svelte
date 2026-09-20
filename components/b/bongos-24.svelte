<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byd26h_vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="byd26h_vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bongos-24" {...props}></Icon>
