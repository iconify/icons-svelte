<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pburr5brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pburr5brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-compact-up" {...props}></Icon>
