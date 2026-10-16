<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpaz5wbyo.css';
import '../../css/g/gzgo2kxbo.css';
import '../../css/b/bvp6t7ksm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qpaz5wbyo"/><path class="gzgo2kxbo"/><path class="bvp6t7ksm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chassis-ground-20" {...props}></Icon>
