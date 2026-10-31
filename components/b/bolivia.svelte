<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6mogacyz.css';
import '../../css/r/raky5r2xx.css';
import '../../css/n/n_rsox0pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="g6mogacyz"/><path class="raky5r2xx"/><path class="n_rsox0pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bolivia" {...props}></Icon>
