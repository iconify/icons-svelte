<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxf5o4ixa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxf5o4ixa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:data-transfer-diagonal-bold" {...props}></Icon>
