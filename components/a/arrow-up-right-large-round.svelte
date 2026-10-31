<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp1lhszbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1lhszbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-large-round" {...props}></Icon>
