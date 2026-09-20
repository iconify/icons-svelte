<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwda_fpmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwda_fpmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dumbbell-1" {...props}></Icon>
