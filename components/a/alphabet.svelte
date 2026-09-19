<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou6jo2k2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ou6jo2k2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:alphabet" {...props}></Icon>
