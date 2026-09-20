<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sslb1u9_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sslb1u9_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:fire" {...props}></Icon>
