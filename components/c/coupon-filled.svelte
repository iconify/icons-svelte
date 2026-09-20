<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzh_mgbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dzh_mgbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:coupon-filled" {...props}></Icon>
