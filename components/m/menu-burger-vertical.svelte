<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhcisp32j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhcisp32j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-vertical" {...props}></Icon>
