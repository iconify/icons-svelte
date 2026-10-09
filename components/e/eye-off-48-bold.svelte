<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udbsvx9ze.css';
import '../../css/x/x6a75wd9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udbsvx9ze"/><path class="x6a75wd9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-off-48-bold" {...props}></Icon>
