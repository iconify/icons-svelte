<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlgtlvbnh.css';
import '../../css/r/rghwx5e1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlgtlvbnh"/><path class="rghwx5e1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:amazon-pay" {...props}></Icon>
