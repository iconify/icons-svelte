<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw-3dzecl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw-3dzecl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:gender-lesbian-2" {...props}></Icon>
