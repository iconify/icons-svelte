<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3cyo1ucc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a3cyo1ucc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:front" {...props}></Icon>
