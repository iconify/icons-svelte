<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgy83lbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgy83lbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-single-right-filled" {...props}></Icon>
