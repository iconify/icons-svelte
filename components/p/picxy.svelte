<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px7f85dfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px7f85dfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:picxy" {...props}></Icon>
