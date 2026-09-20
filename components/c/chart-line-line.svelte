<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg6j7hbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg6j7hbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-line-line" {...props}></Icon>
