<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsw-bb_vv.css';
import '../../css/l/lv1nsoira.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsw-bb_vv"/><path class="lv1nsoira"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-ring" {...props}></Icon>
