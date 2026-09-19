<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbt_o16fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbt_o16fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe" {...props}></Icon>
