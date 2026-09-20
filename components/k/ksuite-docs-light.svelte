<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu6nytwut.css';
import '../../css/d/dt8zsopdi.css';
import '../../css/p/pg98fbbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu6nytwut"/><path class="dt8zsopdi"/><path class="pg98fbbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-docs-light" {...props}></Icon>
