<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7t8ub8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7t8ub8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layer-send-to-back" {...props}></Icon>
