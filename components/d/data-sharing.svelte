<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn5_oubwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn5_oubwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:data-sharing" {...props}></Icon>
