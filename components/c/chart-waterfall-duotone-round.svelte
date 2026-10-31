<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t18l-9bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t18l-9bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-waterfall-duotone-round" {...props}></Icon>
