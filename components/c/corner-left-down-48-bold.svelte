<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z87jsv16f.css';
import '../../css/g/gr2hwkk9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z87jsv16f"/><path class="gr2hwkk9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-down-48-bold" {...props}></Icon>
