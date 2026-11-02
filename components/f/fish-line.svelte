<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqj7ss4gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqj7ss4gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fish-line" {...props}></Icon>
