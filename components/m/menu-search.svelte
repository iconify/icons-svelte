<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4sl_d9vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4sl_d9vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-search" {...props}></Icon>
