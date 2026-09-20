<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuzlabbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuzlabbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qualcomm" {...props}></Icon>
