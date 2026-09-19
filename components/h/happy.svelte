<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub4d63l7m.css';
import '../../css/t/t7y87xbel.css';
import '../../css/d/d47xi2b9o.css';
import '../../css/a/afela-auq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="ub4d63l7m"/><circle class="t7y87xbel"/><path class="d47xi2b9o"/><path class="afela-auq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:happy" {...props}></Icon>
