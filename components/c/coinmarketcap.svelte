<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-aiqo9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-aiqo9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:coinmarketcap" {...props}></Icon>
