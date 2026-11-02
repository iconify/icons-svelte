<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-81hnbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-81hnbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ambulance-line" {...props}></Icon>
