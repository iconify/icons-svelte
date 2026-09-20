<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk4maq4cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gk4maq4cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:larger-text" {...props}></Icon>
