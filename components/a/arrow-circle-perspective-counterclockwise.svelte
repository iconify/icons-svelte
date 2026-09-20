<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3k2hbbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3k2hbbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-circle-perspective-counterclockwise" {...props}></Icon>
