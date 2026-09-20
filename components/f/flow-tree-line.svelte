<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlz3lbr5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlz3lbr5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-tree-line" {...props}></Icon>
