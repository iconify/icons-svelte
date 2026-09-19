<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3fg7597e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3fg7597e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:moving-desk" {...props}></Icon>
