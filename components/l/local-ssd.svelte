<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8m4jds0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8m4jds0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:local-ssd" {...props}></Icon>
