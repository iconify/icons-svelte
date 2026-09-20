<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nismq7tnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nismq7tnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-quaver-off" {...props}></Icon>
