<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc_q9jbdu.css';
import '../../css/c/c5p8reb_m.css';
import '../../css/z/zzxe0-1un.css';
import '../../css/h/h84axl_8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hc_q9jbdu"/><path class="c5p8reb_m"/><path class="zzxe0-1un"/><path class="h84axl_8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:djangorest" {...props}></Icon>
