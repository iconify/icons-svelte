<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo4j70bbm.css';
import '../../css/m/mxmopzb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qo4j70bbm"/><path class="mxmopzb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:droplet-20-bold" {...props}></Icon>
