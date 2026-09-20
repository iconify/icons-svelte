<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn77hbb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn77hbb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apple-pay" {...props}></Icon>
