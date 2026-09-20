<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_5l19lqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_5l19lqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:buffer-stop" {...props}></Icon>
