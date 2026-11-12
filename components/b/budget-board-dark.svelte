<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axg085ttp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axg085ttp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budget-board-dark" {...props}></Icon>
