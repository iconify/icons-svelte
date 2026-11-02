<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me8m6obcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me8m6obcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pause-circle-fill" {...props}></Icon>
