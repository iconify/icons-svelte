<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqo5_yb0w.css';
import '../../css/k/kut36cotc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hqo5_yb0w"/><path class="kut36cotc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hvdc-converter-20-bold" {...props}></Icon>
