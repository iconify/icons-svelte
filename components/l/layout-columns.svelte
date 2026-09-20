<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oouxylmqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oouxylmqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:layout-columns" {...props}></Icon>
