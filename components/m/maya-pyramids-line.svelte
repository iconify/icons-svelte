<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh10bubme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh10bubme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maya-pyramids-line" {...props}></Icon>
