<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqhhrj0le.css';
import '../../css/g/gt9eulz_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhhrj0le"/><path class="gt9eulz_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:nut" {...props}></Icon>
