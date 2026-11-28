<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsaxc_miu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsaxc_miu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ai-chip" {...props}></Icon>
