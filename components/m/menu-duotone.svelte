<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1gljwj9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1gljwj9g primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:menu-duotone" {...props}></Icon>
