<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg3rie7kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg3rie7kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bowl-2-fill" {...props}></Icon>
