<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x42f5accj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="x42f5accj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:expand-arrow-1" {...props}></Icon>
