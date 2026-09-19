<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4aeltbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g4aeltbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:panorama-horizontal" {...props}></Icon>
