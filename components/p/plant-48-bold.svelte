<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyvnanrur.css';
import '../../css/n/nk5v6ac6d.css';
import '../../css/p/pkdbtxbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uyvnanrur"/><path class="nk5v6ac6d"/><path class="pkdbtxbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-48-bold" {...props}></Icon>
