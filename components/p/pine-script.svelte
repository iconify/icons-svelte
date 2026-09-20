<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmbb1eb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmbb1eb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pine-script" {...props}></Icon>
