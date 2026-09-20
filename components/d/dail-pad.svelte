<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukc4lr9sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukc4lr9sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:dail-pad" {...props}></Icon>
