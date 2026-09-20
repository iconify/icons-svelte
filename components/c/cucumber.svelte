<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ev_2b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ev_2b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cucumber" {...props}></Icon>
