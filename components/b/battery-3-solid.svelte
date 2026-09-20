<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvt8_wbay.css';
import '../../css/x/xxvlnybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qvt8_wbay"/><path class="xxvlnybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-3-solid" {...props}></Icon>
