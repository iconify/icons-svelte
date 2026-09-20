<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3j_46yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3j_46yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:microstation" {...props}></Icon>
