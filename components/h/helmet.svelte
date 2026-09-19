<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r79emxjpq.css';
import '../../css/v/v9tsbnbgv.css';
import '../../css/i/i27y6db2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="r79emxjpq"/><path class="v9tsbnbgv"/><path class="i27y6db2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:helmet" {...props}></Icon>
