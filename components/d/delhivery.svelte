<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvfg0bbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvfg0bbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:delhivery" {...props}></Icon>
