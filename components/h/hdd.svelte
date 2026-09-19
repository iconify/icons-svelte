<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sypfpluiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="sypfpluiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hdd" {...props}></Icon>
