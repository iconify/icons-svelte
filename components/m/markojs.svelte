<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcwzz_b1o.css';
import '../../css/r/r1sr9thfn.css';
import '../../css/z/zsvi6ec3s.css';
import '../../css/o/ofukf3pkk.css';
import '../../css/u/u_y240b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xcwzz_b1o"/><path class="r1sr9thfn"/><path class="zsvi6ec3s"/><path class="ofukf3pkk"/><path class="u_y240b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:markojs" {...props}></Icon>
