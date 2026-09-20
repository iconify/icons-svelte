<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm55c-0qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nm55c-0qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:envelope" {...props}></Icon>
