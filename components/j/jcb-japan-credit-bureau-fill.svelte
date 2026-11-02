<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geb_t6bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geb_t6bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jcb-japan-credit-bureau-fill" {...props}></Icon>
