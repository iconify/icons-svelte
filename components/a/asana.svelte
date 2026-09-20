<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh-3yd6mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh-3yd6mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:asana" {...props}></Icon>
