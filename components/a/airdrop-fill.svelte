<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0uhiy9nl.css';
import '../../css/f/fwin0va_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0uhiy9nl"/><path class="fwin0va_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airdrop-fill" {...props}></Icon>
