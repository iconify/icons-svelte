<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkknvtmjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkknvtmjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:diagonal-scroll-1-solid" {...props}></Icon>
