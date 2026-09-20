<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_xrf_70t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_xrf_70t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reel-filled" {...props}></Icon>
