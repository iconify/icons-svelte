<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxlczvqqd.css';
import '../../css/m/m8_h6-bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pxlczvqqd"/><path clip-rule="evenodd" class="m8_h6-bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:credit-card-solid" {...props}></Icon>
