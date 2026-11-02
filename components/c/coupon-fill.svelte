<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar4fpmb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar4fpmb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coupon-fill" {...props}></Icon>
