<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1sw88bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1sw88bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quarter-circle-dash-line" {...props}></Icon>
