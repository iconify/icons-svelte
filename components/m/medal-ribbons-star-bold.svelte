<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lij9yb37t.css';
import '../../css/d/dq8mdnoxf.css';
import '../../css/x/xrzk5dbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lij9yb37t"/><path class="dq8mdnoxf"/><path clip-rule="evenodd" class="xrzk5dbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-bold" {...props}></Icon>
