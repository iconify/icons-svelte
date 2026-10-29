<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a11cikskf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a11cikskf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-note" {...props}></Icon>
