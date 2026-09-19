<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv82l7bbi.css';
import '../../css/o/ob530gbzg.css';
import '../../css/g/g8n8bnbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv82l7bbi"/><rect class="ob530gbzg"/><rect class="g8n8bnbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chart-bar-big-columns-filled" {...props}></Icon>
