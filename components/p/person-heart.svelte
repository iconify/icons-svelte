<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quicy360w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="quicy360w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-heart" {...props}></Icon>
