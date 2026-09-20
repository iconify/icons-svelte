<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b08b-lb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b08b-lb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eyedropper-minus" {...props}></Icon>
