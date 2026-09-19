<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xavhm5b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xavhm5b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pin" {...props}></Icon>
