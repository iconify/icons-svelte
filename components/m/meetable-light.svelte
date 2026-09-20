<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7-njbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wk7-njbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meetable-light" {...props}></Icon>
