<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzv-enb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzv-enb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hotel-check" {...props}></Icon>
