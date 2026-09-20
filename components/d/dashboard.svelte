<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jqkjdpbqp.css';
import '../../css/d/dudpnibai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jqkjdpbqp"/><path class="dudpnibai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:dashboard" {...props}></Icon>
