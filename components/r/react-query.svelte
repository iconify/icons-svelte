<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtz70zbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtz70zbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:react-query" {...props}></Icon>
