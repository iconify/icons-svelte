<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pppbkvj-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pppbkvj-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bench-jsx" {...props}></Icon>
