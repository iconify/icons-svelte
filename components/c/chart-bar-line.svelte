<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js32145gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js32145gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-line" {...props}></Icon>
