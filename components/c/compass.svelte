<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufgy1p4li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ufgy1p4li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:compass" {...props}></Icon>
