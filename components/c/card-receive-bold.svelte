<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ie5jj8_jh.css';
import '../../css/g/gafy37gmj.css';
import '../../css/t/tbw_k9bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ie5jj8_jh"/><path class="gafy37gmj"/><path clip-rule="evenodd" class="tbw_k9bpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-receive-bold" {...props}></Icon>
