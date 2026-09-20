<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux02sgbdo.css';
import '../../css/a/aqhlej3kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ux02sgbdo"/><path class="aqhlej3kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-ambulance-call" {...props}></Icon>
