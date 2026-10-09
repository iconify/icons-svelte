<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1w_vbdk.css';
import '../../css/m/mmw4hdxlw.css';
import '../../css/c/c_lk71bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mq1w_vbdk"/><path class="mmw4hdxlw"/><path class="c_lk71bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-20-bold" {...props}></Icon>
