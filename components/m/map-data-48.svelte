<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvjwhfbog.css';
import '../../css/b/bxn05tnng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvjwhfbog"/><path class="bxn05tnng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-data-48" {...props}></Icon>
