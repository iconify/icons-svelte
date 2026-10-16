<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm-ms1i2h.css';
import '../../css/x/xe4qnpbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hm-ms1i2h"/><path class="xe4qnpbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-cross-20" {...props}></Icon>
