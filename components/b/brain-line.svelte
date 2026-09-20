<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re694ccje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re694ccje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brain-line" {...props}></Icon>
