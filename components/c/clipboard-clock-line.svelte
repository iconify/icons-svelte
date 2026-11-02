<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_-6zsbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_-6zsbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-clock-line" {...props}></Icon>
