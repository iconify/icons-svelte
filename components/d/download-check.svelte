<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdk7-cbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdk7-cbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:download-check" {...props}></Icon>
