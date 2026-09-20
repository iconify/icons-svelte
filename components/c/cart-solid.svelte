<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw20fcbyu.css';
import '../../css/d/ds8m3ccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kw20fcbyu"/><path clip-rule="evenodd" class="ds8m3ccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cart-solid" {...props}></Icon>
