<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klk31e80v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klk31e80v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-flush-circular" {...props}></Icon>
