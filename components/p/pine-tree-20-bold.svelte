<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k97abjb9v.css';
import '../../css/g/gtbcxr-sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k97abjb9v"/><path class="gtbcxr-sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pine-tree-20-bold" {...props}></Icon>
