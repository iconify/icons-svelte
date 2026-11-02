<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg2gc29iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg2gc29iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-tree-line" {...props}></Icon>
