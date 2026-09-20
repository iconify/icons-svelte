<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6h0jugoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6h0jugoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right-bold-box" {...props}></Icon>
