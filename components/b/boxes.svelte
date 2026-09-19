<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdxul1sda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hdxul1sda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:boxes" {...props}></Icon>
