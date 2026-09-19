<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx7pr52qg.css';
import '../../css/x/xpexa2b0b.css';
import '../../css/j/jinb6ibrg.css';
import '../../css/d/doz_8wbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bx7pr52qg"/><circle class="xpexa2b0b"/><circle class="jinb6ibrg"/><circle class="doz_8wbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:list-outline" {...props}></Icon>
