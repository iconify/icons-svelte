<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy2w5v7zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy2w5v7zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:box-filled" {...props}></Icon>
