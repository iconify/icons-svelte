<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a61q8-b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a61q8-b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-circle-fill" {...props}></Icon>
