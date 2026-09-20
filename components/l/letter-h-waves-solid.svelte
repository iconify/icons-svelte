<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum4ihblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oum4ihblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-waves-solid" {...props}></Icon>
