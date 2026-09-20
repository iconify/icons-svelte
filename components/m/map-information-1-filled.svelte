<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw--zdb9h.css';
import '../../css/k/k5i8z-b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw--zdb9h"/><path class="k5i8z-b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-information-1-filled" {...props}></Icon>
