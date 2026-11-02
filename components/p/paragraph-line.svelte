<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mswc7wb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mswc7wb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paragraph-line" {...props}></Icon>
