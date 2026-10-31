<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az078c_gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az078c_gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-check-fill-round" {...props}></Icon>
