<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilianfni.css';
import '../../css/s/s0v63acst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="s0v63acst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-child" {...props}></Icon>
