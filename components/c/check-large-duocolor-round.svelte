<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr1rxcrhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr1rxcrhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-large-duocolor-round" {...props}></Icon>
