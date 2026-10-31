<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkkp9mbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkkp9mbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cupid-bow-gloss" {...props}></Icon>
