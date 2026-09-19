<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4haehu2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s4haehu2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:happy-face" {...props}></Icon>
