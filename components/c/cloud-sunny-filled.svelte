<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww_3snb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww_3snb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-sunny-filled" {...props}></Icon>
