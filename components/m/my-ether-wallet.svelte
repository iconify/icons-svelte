<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xujzs6iss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xujzs6iss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:my-ether-wallet" {...props}></Icon>
