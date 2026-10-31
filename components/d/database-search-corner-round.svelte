<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjocuyzej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjocuyzej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-search-corner-round" {...props}></Icon>
