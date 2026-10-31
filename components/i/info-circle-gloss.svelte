<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9mbz718s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9mbz718s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:info-circle-gloss" {...props}></Icon>
