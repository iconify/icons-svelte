<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jscfo15-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jscfo15-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment" {...props}></Icon>
