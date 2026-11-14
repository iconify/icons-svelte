<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsdz9kqpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsdz9kqpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:outdoor-motion" {...props}></Icon>
