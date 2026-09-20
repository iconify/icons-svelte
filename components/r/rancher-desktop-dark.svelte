<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9aa4q98x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9aa4q98x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-desktop-dark" {...props}></Icon>
