<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cso4l-5ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cso4l-5ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:malaria-pv-microscope" {...props}></Icon>
