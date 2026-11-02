<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi751op0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi751op0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:meh-line" {...props}></Icon>
