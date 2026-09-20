<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nya56cc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nya56cc1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:currency-sign-won-coupon-bold" {...props}></Icon>
