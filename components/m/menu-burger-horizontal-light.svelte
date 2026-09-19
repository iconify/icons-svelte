<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfx5qrwbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfx5qrwbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-horizontal-light" {...props}></Icon>
