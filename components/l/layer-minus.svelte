<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc9dwfbws.css';
import '../../css/h/hj974yb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc9dwfbws"/><path class="hj974yb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:layer-minus" {...props}></Icon>
