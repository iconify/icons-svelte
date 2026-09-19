<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su70yibof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su70yibof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:kotlin" {...props}></Icon>
