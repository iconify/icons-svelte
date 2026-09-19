<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb4fn3bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nb4fn3bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:heart-ballon" {...props}></Icon>
