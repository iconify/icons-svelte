<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_ty2ebyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_ty2ebyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:keyhole-square-bold" {...props}></Icon>
