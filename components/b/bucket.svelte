<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twdnh2b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="twdnh2b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bucket" {...props}></Icon>
