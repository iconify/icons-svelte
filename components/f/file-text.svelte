<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmc3uq-pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nmc3uq-pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-text" {...props}></Icon>
