<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfibukysa.css';
import '../../css/e/ei2sh0bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lfibukysa"/><path class="ei2sh0bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:desk-adjustable" {...props}></Icon>
