<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9t3z0jdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9t3z0jdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-up-gloss" {...props}></Icon>
