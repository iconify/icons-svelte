<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsymhfbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wsymhfbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-fill-16" {...props}></Icon>
