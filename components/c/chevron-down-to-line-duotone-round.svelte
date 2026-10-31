<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibunlsb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibunlsb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-to-line-duotone-round" {...props}></Icon>
