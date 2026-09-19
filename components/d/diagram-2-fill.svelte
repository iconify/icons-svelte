<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z08c56b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z08c56b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diagram-2-fill" {...props}></Icon>
