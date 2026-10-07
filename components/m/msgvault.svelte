<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rod24kbrj.css';
import '../../css/y/y20r2pbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rod24kbrj"/><path class="y20r2pbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:msgvault" {...props}></Icon>
