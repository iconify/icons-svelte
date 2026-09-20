<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n2pw1mffs.css';
import '../../css/f/f7azv0kip.css';
import '../../css/g/gyeonr9rw.css';
import '../../css/c/cahl0fbfp.css';
import '../../css/e/ex9vehb3q.css';
import '../../css/y/yre2wm67g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n2pw1mffs"/><path class="f7azv0kip"/><path class="gyeonr9rw"/><path class="cahl0fbfp"/><path class="ex9vehb3q"/><path class="yre2wm67g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-broken" {...props}></Icon>
