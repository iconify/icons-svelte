<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aumdvgb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aumdvgb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:obelisk" {...props}></Icon>
