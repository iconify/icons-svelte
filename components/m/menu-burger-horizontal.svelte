<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byqlfobep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byqlfobep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-horizontal" {...props}></Icon>
