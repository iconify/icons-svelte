<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1fwirb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fwirb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-percent-gloss" {...props}></Icon>
