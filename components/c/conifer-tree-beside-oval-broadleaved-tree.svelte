<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwyekn-8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jwyekn-8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-beside-oval-broadleaved-tree" {...props}></Icon>
