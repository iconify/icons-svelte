<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6s329bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6s329bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-tree-solid" {...props}></Icon>
