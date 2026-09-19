<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b48_ecc_g.css';
import '../../css/x/x01waj_-c.css';
import '../../css/b/ba80-obkp.css';
import '../../css/z/zgr1wqj3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b48_ecc_g"/><path class="x01waj_-c"/><path class="ba80-obkp"/><path class="zgr1wqj3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:documents-outline" {...props}></Icon>
