<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdfbblb0o.css';
import '../../css/l/l78-x2byw.css';
import '../../css/e/eghcg3_xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdfbblb0o"/><path class="l78-x2byw"/><path class="eghcg3_xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:index" {...props}></Icon>
