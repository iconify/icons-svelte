<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-7le-bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":448};
const content = `<path class="h-7le-bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:couple" {...props}></Icon>
