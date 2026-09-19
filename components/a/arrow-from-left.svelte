<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxb_yw1vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxb_yw1vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-from-left" {...props}></Icon>
