<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcpzrab3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcpzrab3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-add" {...props}></Icon>
