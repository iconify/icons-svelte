<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n2a2z7bro.css';
import '../../css/e/esqpnhuzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="n2a2z7bro"/><path class="esqpnhuzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cosmoshub" {...props}></Icon>
