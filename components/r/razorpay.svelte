<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl8-cidno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl8-cidno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:razorpay" {...props}></Icon>
