<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8kieuq1v.css';
import '../../css/d/d-w_kffol.css';
import '../../css/x/x-p659jvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v8kieuq1v"/><path class="d-w_kffol"/><path class="x-p659jvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-health-20-bold" {...props}></Icon>
