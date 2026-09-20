<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqcrpce7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqcrpce7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-paypal-filled" {...props}></Icon>
