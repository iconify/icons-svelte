<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_vaous8i.css';
import '../../css/y/yze3d2bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vaous8i"/><path class="yze3d2bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-down-filled" {...props}></Icon>
