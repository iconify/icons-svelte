<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3muasauf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="n3muasauf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:accounts-list-alt" {...props}></Icon>
