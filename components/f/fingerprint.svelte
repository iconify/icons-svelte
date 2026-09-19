<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml7zczbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7zczbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:fingerprint" {...props}></Icon>
