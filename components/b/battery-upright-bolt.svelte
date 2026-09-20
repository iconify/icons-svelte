<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn-2mgv2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qn-2mgv2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-bolt" {...props}></Icon>
