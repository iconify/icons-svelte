<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsj_mfb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsj_mfb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:doctor-03" {...props}></Icon>
