<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn_94diua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pn_94diua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:loading-four" {...props}></Icon>
