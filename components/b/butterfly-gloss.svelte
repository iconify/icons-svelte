<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7lmykrat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7lmykrat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:butterfly-gloss" {...props}></Icon>
