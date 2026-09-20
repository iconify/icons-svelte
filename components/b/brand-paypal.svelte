<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up6bcgbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up6bcgbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-paypal" {...props}></Icon>
