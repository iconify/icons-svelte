<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb-8z_bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb-8z_bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-plus" {...props}></Icon>
