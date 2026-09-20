<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctweey_bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ctweey_bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pig" {...props}></Icon>
