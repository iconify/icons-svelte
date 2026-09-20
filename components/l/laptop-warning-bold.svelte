<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_ggsobwy.css';
import '../../css/g/gxkm953bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_ggsobwy"/><path class="gxkm953bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laptop-warning-bold" {...props}></Icon>
