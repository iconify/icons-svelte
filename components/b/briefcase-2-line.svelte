<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_804bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le_804bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-2-line" {...props}></Icon>
