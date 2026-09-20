<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c76_bpbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c76_bpbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:media" {...props}></Icon>
