<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p17sbobkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p17sbobkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:edit-light" {...props}></Icon>
