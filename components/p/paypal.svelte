<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh6no0b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="lh6no0b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:paypal" {...props}></Icon>
