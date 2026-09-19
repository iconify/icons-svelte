<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owx_5mb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="owx_5mb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:paypal-p" {...props}></Icon>
