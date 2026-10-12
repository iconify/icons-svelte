<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cysjv4btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cysjv4btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-circle-fill-20" {...props}></Icon>
