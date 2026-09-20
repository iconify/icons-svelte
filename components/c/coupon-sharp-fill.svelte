<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlg1ftb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlg1ftb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:coupon-sharp-fill" {...props}></Icon>
