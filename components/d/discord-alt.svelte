<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jminnsb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jminnsb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:discord-alt" {...props}></Icon>
