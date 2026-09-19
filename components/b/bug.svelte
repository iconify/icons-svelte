<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo0k1bywm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo0k1bywm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bug" {...props}></Icon>
