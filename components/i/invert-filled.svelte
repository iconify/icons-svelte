<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpxmm_7co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpxmm_7co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:invert-filled" {...props}></Icon>
