<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj1c4pbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj1c4pbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-graph-gloss" {...props}></Icon>
