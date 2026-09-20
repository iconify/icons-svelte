<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-id9i7nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j-id9i7nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-under-list-beside-checkmark" {...props}></Icon>
