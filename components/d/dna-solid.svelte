<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0a56ysln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0a56ysln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dna-solid" {...props}></Icon>
