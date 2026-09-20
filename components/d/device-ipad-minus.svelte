<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjxv-8b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjxv-8b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-minus" {...props}></Icon>
