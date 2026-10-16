<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b24n32b6u.css';
import '../../css/j/jdj652_du.css';
import '../../css/m/m-d02bb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b24n32b6u"/><path class="jdj652_du"/><path class="m-d02bb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-tree-20-bold" {...props}></Icon>
