<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdm3i3bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qdm3i3bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:people-carry" {...props}></Icon>
