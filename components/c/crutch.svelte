<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwq7ipbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwq7ipbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:crutch" {...props}></Icon>
