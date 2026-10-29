<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyo6qebbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyo6qebbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:person-standing-solid" {...props}></Icon>
