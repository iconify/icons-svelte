<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvizkus5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bvizkus5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:replay-10-fill" {...props}></Icon>
