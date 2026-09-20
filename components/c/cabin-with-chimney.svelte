<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk51rwbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fk51rwbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cabin-with-chimney" {...props}></Icon>
