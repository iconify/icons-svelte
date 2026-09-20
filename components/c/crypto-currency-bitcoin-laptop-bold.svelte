<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmd-u2nlq.css';
import '../../css/a/axndlm-lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmd-u2nlq"/><path class="axndlm-lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:crypto-currency-bitcoin-laptop-bold" {...props}></Icon>
