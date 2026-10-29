<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bti7alb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bti7alb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:palm-tree-solid" {...props}></Icon>
