<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p79vmbtic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p79vmbtic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:juejin" {...props}></Icon>
