<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyu7psbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gyu7psbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:doughnutchart" {...props}></Icon>
