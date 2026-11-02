<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1jh9or0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1jh9or0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-3-fill" {...props}></Icon>
