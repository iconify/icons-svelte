<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp4g854do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp4g854do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-dash-line" {...props}></Icon>
