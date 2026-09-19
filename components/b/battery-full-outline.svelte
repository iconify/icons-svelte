<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/ynz9scf9p.css';
import '../../css/n/n3rgr7haw.css';
import '../../css/f/fvzgndqwy.css';
import '../../css/l/llq415oom.css';
import '../../css/l/lttb5bslb.css';
import '../../css/u/unxdowbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ynz9scf9p"/><rect class="n3rgr7haw"/><rect class="fvzgndqwy"/><rect class="llq415oom"/><rect class="lttb5bslb"/><path class="unxdowbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:battery-full-outline" {...props}></Icon>
