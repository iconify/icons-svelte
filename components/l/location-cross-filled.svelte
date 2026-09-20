<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxqi0yxyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxqi0yxyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:location-cross-filled" {...props}></Icon>
