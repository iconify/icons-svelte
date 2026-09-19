<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr0_a1bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr0_a1bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-right-01" {...props}></Icon>
