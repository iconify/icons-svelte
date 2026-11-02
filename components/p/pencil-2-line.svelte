<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyykz9z8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyykz9z8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-line" {...props}></Icon>
