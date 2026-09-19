<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbp1j9bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbp1j9bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:citadel-filled" {...props}></Icon>
