<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdzw-5b-o.css';
import '../../css/c/cargn6b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdzw-5b-o"/><path class="cargn6b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oneuptime" {...props}></Icon>
