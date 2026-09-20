<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd74-c-sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd74-c-sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-2-fill" {...props}></Icon>
