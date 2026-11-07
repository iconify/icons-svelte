<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4b_ewb5v.css';
import '../../css/l/llk64db4t.css';
import '../../css/t/t000zacqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4b_ewb5v"/><path class="llk64db4t"/><path clip-rule="evenodd" class="t000zacqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-quote-bold" {...props}></Icon>
