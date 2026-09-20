<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odtdr55ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="odtdr55ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-dollar-remix" {...props}></Icon>
