<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4c5qeb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4c5qeb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-line" {...props}></Icon>
