<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgu-cdbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgu-cdbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keila" {...props}></Icon>
