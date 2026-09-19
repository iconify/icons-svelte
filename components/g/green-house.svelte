<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqtpnnt2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqtpnnt2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:green-house" {...props}></Icon>
