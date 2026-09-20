<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tip5qcczg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tip5qcczg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-wrench" {...props}></Icon>
