<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_0c644vy.css';
import '../../css/q/q4_c29bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_0c644vy"/><path class="q4_c29bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cupboard" {...props}></Icon>
