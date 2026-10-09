<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtawmliso.css';
import '../../css/u/ulvnhe8jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtawmliso"/><path class="ulvnhe8jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pizza-slice-48" {...props}></Icon>
