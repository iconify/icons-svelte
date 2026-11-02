<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huucxrbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huucxrbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:infinity-2-fill" {...props}></Icon>
