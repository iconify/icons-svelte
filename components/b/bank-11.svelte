<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynyh7db1r.css';
import '../../css/t/th8xxac7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ynyh7db1r"/><path class="th8xxac7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bank-11" {...props}></Icon>
