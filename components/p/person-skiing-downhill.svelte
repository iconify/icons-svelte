<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7zezab6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d7zezab6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-skiing-downhill" {...props}></Icon>
