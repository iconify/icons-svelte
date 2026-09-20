<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3bp1l9tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y3bp1l9tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:board-heavy-rail" {...props}></Icon>
