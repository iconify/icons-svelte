<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b82tnpazp.css';
import '../../css/u/u6jj-hn4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b82tnpazp"/><path class="u6jj-hn4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:needleleaved-tree-urban-tree-pot" {...props}></Icon>
