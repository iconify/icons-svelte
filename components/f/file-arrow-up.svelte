<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blyj3u2pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blyj3u2pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-arrow-up" {...props}></Icon>
