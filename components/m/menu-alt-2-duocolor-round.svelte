<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7-cenqsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7-cenqsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-2-duocolor-round" {...props}></Icon>
