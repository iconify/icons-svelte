<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgxvwt_3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="kgxvwt_3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ambulance" {...props}></Icon>
