<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m681rhb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m681rhb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-window-line" {...props}></Icon>
