<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d46e2yb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d46e2yb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:building-tree-fill" {...props}></Icon>
