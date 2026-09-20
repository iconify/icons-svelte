<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl7wdwbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bl7wdwbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-cricket-batting-at-cricket-ball" {...props}></Icon>
