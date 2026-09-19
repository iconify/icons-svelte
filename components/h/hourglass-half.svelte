<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daqkvwn8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="daqkvwn8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hourglass-half" {...props}></Icon>
