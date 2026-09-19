<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atr529omg.css';
import '../../css/t/tlb5s_7xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atr529omg"/><path class="tlb5s_7xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chat" {...props}></Icon>
