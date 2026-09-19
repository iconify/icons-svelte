<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkv516bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkv516bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:ramp-down" {...props}></Icon>
