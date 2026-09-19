<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdx__9a1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bdx__9a1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-merge-left-filled" {...props}></Icon>
