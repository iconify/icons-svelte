<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_z99bhx.css';
import '../../css/r/rmban7b_u.css';
import '../../css/z/zho782gha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="rmban7b_u"/><path class="zho782gha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:report-48" {...props}></Icon>
