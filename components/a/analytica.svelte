<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eph5_wbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eph5_wbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:analytica" {...props}></Icon>
