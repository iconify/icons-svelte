<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8odnb1pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w8odnb1pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-down-square-fill" {...props}></Icon>
