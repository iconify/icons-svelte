<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsl5haset.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsl5haset"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coupon-line" {...props}></Icon>
