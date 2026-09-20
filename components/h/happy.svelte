<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgyhjfdlw.css';
import '../../css/v/v4-7eu8rv.css';
import '../../css/f/f84x_gb3e.css';
import '../../css/o/of7d1zb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tgyhjfdlw"/><path class="v4-7eu8rv"/><circle class="f84x_gb3e"/><circle class="of7d1zb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:happy" {...props}></Icon>
