<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-b4wo2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ok-b4wo2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rocket-fill-16" {...props}></Icon>
