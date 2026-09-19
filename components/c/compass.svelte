<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxhihb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nuxhihb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:compass" {...props}></Icon>
