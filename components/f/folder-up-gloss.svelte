<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dryk-bb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dryk-bb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-up-gloss" {...props}></Icon>
