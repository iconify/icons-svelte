<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-h8wbdp.css';
import '../../css/u/u7oeflsek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be-h8wbdp"/><path class="u7oeflsek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-horizontal-line" {...props}></Icon>
