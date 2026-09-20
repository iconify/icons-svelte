<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbr64l8xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr64l8xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:500px" {...props}></Icon>
