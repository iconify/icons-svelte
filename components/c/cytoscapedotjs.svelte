<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/locxbymvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="locxbymvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cytoscapedotjs" {...props}></Icon>
