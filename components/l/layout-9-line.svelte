<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llcarc34f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llcarc34f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-9-line" {...props}></Icon>
