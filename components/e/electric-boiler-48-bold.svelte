<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae3ox-mnm.css';
import '../../css/p/pook9-t4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ae3ox-mnm"/><path class="pook9-t4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boiler-48-bold" {...props}></Icon>
