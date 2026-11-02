<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcx5dkeqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcx5dkeqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-horizontal-end-fill" {...props}></Icon>
