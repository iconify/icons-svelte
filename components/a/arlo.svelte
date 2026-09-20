<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh89h7rhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh89h7rhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arlo" {...props}></Icon>
