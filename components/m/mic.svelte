<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y82qfw6rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y82qfw6rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:mic" {...props}></Icon>
