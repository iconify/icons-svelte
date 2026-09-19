<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgl8xnb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zgl8xnb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-text-middle" {...props}></Icon>
