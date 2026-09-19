<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p57ynbb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p57ynbb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:record" {...props}></Icon>
