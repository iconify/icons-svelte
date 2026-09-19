<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9k2uvbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c9k2uvbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart" {...props}></Icon>
