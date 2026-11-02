<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaneb2bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaneb2bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leo-fill" {...props}></Icon>
