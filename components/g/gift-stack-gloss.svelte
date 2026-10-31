<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czkks7lgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czkks7lgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gift-stack-gloss" {...props}></Icon>
