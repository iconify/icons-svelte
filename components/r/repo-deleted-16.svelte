<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4gl7ubxp.css';
import '../../css/m/m76ihyh3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q4gl7ubxp"/><path class="m76ihyh3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-deleted-16" {...props}></Icon>
