<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4vl0yfzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4vl0yfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-s-charge" {...props}></Icon>
