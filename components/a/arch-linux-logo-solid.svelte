<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc61b2bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc61b2bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:arch-linux-logo-solid" {...props}></Icon>
