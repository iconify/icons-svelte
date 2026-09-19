<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz3-xgbbc.css';
import '../../css/l/lw8ky0vfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pz3-xgbbc"/><path class="lw8ky0vfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:banknotedollar" {...props}></Icon>
