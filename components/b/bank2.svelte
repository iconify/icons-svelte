<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb6theb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hb6theb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bank2" {...props}></Icon>
