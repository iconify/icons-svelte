<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3g-t4buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3g-t4buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codeship" {...props}></Icon>
