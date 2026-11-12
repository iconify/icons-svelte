<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/modagxbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="modagxbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oracle" {...props}></Icon>
