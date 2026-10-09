<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeyn_tb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qeyn_tb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:menu-48" {...props}></Icon>
