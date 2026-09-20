<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4s140a6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="l4s140a6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:residential-community-11" {...props}></Icon>
