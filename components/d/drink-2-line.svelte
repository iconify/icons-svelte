<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzmytcyfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzmytcyfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drink-2-line" {...props}></Icon>
