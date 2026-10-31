<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecn-l84yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecn-l84yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-rupee-duotone-round" {...props}></Icon>
