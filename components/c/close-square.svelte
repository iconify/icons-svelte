<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy-64abzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xy-64abzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:close-square" {...props}></Icon>
