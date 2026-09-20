<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yya7h_b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yya7h_b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pin" {...props}></Icon>
