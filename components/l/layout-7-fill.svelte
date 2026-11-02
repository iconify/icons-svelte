<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw-1_aciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw-1_aciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-7-fill" {...props}></Icon>
