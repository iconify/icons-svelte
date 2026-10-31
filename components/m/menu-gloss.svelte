<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sprf0kjfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sprf0kjfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:menu-gloss" {...props}></Icon>
