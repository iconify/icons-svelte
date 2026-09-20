<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfi7w5aob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfi7w5aob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:amkt" {...props}></Icon>
