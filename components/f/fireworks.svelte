<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/eas391big.css';
import '../../css/y/y9pme5b7n.css';
import '../../css/g/gtv82xhfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eas391big"/><path class="y9pme5b7n"/><path class="gtv82xhfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fireworks" {...props}></Icon>
