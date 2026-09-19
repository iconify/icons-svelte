<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsl2t2bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsl2t2bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:circle" {...props}></Icon>
