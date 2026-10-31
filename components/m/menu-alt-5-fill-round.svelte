<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rha5-6c-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rha5-6c-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-5-fill-round" {...props}></Icon>
