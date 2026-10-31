<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx_-4bcbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_-4bcbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ear-fill-round" {...props}></Icon>
