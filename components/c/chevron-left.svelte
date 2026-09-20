<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc-3dgb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qc-3dgb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chevron-left" {...props}></Icon>
