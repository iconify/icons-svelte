<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq1jtnbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq1jtnbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:airplane-sharp" {...props}></Icon>
