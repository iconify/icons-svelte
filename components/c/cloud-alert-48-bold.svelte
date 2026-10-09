<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-8v5fp5o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/x/x-w4dbc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l-8v5fp5o"/><path class="hwjgqrbah"/><path class="x-w4dbc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-alert-48-bold" {...props}></Icon>
