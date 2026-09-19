<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7n7kbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ym7n7kbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-spock" {...props}></Icon>
