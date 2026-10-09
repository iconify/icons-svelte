<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z79_i2hkx.css';
import '../../css/h/hu2zm7ich.css';
import '../../css/z/zlii3abwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z79_i2hkx"/><path class="hu2zm7ich"/><path class="zlii3abwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cell-20" {...props}></Icon>
