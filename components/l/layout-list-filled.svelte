<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr_-ibcyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr_-ibcyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-list-filled" {...props}></Icon>
