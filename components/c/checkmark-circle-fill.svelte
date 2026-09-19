<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7_r22bur.css';
import '../../css/z/zchckjb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7_r22bur"/><path class="zchckjb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:checkmark-circle-fill" {...props}></Icon>
