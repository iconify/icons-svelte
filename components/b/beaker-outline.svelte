<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv5ugxbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv5ugxbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:beaker-outline" {...props}></Icon>
