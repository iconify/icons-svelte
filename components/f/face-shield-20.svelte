<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax9d5gbpa.css';
import '../../css/w/w6rxgvl3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ax9d5gbpa"/><path class="w6rxgvl3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-shield-20" {...props}></Icon>
