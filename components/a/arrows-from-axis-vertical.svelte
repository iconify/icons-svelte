<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktlm67gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dktlm67gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-from-axis-vertical" {...props}></Icon>
