<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kury_foqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kury_foqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:attention-solid-sm" {...props}></Icon>
