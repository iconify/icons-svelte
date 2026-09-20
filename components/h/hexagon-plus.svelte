<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn_0d_bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_0d_bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-plus" {...props}></Icon>
