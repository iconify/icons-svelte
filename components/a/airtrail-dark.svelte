<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmw0dtjti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmw0dtjti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airtrail-dark" {...props}></Icon>
