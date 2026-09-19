<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd39-q0pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":850};
const content = `<path class="hd39-q0pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:mic" {...props}></Icon>
