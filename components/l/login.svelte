<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzx31b0pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzx31b0pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:login" {...props}></Icon>
