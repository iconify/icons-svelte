<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhjxt_l_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjxt_l_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:feed" {...props}></Icon>
