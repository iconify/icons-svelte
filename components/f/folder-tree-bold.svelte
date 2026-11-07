<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by22ydp5s.css';
import '../../css/j/j7a0fv5du.css';
import '../../css/e/el9y-0crz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by22ydp5s"/><path class="j7a0fv5du"/><path class="el9y-0crz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-tree-bold" {...props}></Icon>
