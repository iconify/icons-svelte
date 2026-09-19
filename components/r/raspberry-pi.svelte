<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek80r3bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="ek80r3bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:raspberry-pi" {...props}></Icon>
