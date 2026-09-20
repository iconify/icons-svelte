<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn1c_rh4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn1c_rh4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-types" {...props}></Icon>
