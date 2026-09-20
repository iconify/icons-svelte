<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtrkdubov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xtrkdubov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:new-jersey" {...props}></Icon>
