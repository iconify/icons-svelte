<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx_bh6bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_bh6bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-up-filled" {...props}></Icon>
