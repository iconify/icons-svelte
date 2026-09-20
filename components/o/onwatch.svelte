<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faxt378lm.css';
import '../../css/e/ezv3-gbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="faxt378lm"/><path class="ezv3-gbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onwatch" {...props}></Icon>
