<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvpdrtm6x.css';
import '../../css/k/kgx7jsbsk.css';
import '../../css/h/hayl1lfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lvpdrtm6x"/><path class="kgx7jsbsk"/><path class="hayl1lfmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-minus-20-bold" {...props}></Icon>
