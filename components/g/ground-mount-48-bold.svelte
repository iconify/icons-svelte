<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu2obeb0g.css';
import '../../css/p/p8dn0lt6q.css';
import '../../css/d/d6cvwtbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mu2obeb0g"/><path class="p8dn0lt6q"/><path class="d6cvwtbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-mount-48-bold" {...props}></Icon>
