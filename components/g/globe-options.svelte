<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkmm-1g0c.css';
import '../../css/h/h1ytemzns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tkmm-1g0c"/><path class="h1ytemzns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-options" {...props}></Icon>
