<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhk70wg4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhk70wg4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-blogger" {...props}></Icon>
