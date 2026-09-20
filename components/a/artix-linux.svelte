<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrs9bx7bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrs9bx7bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:artix-linux" {...props}></Icon>
