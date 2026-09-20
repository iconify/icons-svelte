<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg1mcz04c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xg1mcz04c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:octopus-solid" {...props}></Icon>
