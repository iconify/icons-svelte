<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd_g2tb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd_g2tb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dribbling-filled" {...props}></Icon>
