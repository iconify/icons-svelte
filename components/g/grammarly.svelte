<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usf8_8x2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usf8_8x2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:grammarly" {...props}></Icon>
