<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5w6t-_yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5w6t-_yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:guitarpro" {...props}></Icon>
