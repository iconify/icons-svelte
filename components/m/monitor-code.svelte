<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nne87hv2x.css';
import '../../css/b/bfaiweb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nne87hv2x"/><path class="bfaiweb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:monitor-code" {...props}></Icon>
