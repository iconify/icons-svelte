<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_-65y1bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_-65y1bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-fill" {...props}></Icon>
