<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bao1vbqnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bao1vbqnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:christmas-tree-one" {...props}></Icon>
