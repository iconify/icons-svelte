<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2p4y856r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k2p4y856r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:git" {...props}></Icon>
