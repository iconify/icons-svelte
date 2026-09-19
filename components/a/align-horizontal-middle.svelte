<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzzx31bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gzzx31bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-horizontal-middle" {...props}></Icon>
