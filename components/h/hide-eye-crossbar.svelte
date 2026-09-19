<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-1demrtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-1demrtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:hide-eye-crossbar" {...props}></Icon>
