<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzdx2iy2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mzdx2iy2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-plus-solid" {...props}></Icon>
