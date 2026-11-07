<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li7-h_b7c.css';
import '../../css/u/uq0t-hbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li7-h_b7c"/><path class="uq0t-hbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-bold-duotone" {...props}></Icon>
