<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwvlvvbmr.css';
import '../../css/l/l66nyjbec.css';
import '../../css/f/fw-va7bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvlvvbmr"/><path class="l66nyjbec"/><path class="fw-va7bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mana" {...props}></Icon>
