<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yed5v9b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="yed5v9b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-chimney-user" {...props}></Icon>
