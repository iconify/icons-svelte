<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv33hva9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yv33hva9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:pencil-square" {...props}></Icon>
