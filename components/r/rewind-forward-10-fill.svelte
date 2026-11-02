<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg2irbcwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg2irbcwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-10-fill" {...props}></Icon>
