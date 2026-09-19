<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd7ji-5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qd7ji-5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:opa" {...props}></Icon>
