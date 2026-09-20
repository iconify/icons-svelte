<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdxfm_-fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bdxfm_-fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-outline-with-info-i" {...props}></Icon>
