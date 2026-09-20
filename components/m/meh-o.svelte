<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-wdvunml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y-wdvunml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:meh-o" {...props}></Icon>
