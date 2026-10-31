<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvy5cdb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvy5cdb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane-gloss" {...props}></Icon>
