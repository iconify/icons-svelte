<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdau2pj7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdau2pj7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:airtel" {...props}></Icon>
