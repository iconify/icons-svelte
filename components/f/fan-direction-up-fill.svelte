<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-55cwyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-55cwyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-up-fill" {...props}></Icon>
