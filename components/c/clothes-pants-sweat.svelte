<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz8-vsbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sz8-vsbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clothes-pants-sweat" {...props}></Icon>
