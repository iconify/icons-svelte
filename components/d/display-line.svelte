<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk2o1b0nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk2o1b0nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:display-line" {...props}></Icon>
