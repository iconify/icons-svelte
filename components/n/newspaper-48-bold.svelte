<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uph6w3b8p.css';
import '../../css/q/qo92-j1px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uph6w3b8p"/><path class="qo92-j1px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:newspaper-48-bold" {...props}></Icon>
