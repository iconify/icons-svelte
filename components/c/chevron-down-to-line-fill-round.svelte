<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbpay4bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbpay4bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-to-line-fill-round" {...props}></Icon>
