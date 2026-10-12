<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhuzgciui.css';
import '../../css/s/s-e7f6v_f.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/x/xwdhawfba.css';
import '../../css/h/hayl1lfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhuzgciui"/><path class="s-e7f6v_f"/><path class="aqsnv9bnd"/><path class="xwdhawfba"/><path class="hayl1lfmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-plus-20-bold" {...props}></Icon>
