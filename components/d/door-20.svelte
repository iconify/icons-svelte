<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqvv3bb7y.css';
import '../../css/t/ti-bis8gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kqvv3bb7y"/><path class="ti-bis8gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:door-20" {...props}></Icon>
