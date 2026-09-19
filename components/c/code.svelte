<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl8o-nbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="pl8o-nbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:code" {...props}></Icon>
