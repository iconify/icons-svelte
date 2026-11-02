<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbq8t_bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbq8t_bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-down-line" {...props}></Icon>
