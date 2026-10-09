<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8mp0wbzm.css';
import '../../css/r/r1wj_pscx.css';
import '../../css/t/t8srk-ced.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="r1wj_pscx"/><path class="t8srk-ced"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-storage-48" {...props}></Icon>
