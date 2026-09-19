<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z64gnu31o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":24};
const content = `<path class="z64gnu31o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mongodb" {...props}></Icon>
