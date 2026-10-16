<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsv726byj.css';
import '../../css/w/w0t6-kbpw.css';
import '../../css/v/ve_svj3jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tsv726byj"/><path class="w0t6-kbpw"/><path class="ve_svj3jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iot-device-20-bold" {...props}></Icon>
