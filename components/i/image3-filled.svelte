<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv6o-j_2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv6o-j_2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:image3-filled" {...props}></Icon>
