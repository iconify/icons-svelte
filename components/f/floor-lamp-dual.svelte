<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iauqty01z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iauqty01z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:floor-lamp-dual" {...props}></Icon>
