<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5rak2bbx.css';
import '../../css/i/iyuvrebaw.css';
import '../../css/c/cnvsi8cop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5rak2bbx"/><path class="iyuvrebaw"/><path class="cnvsi8cop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plumb-bob-48-bold" {...props}></Icon>
