<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpfjnxb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lpfjnxb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rocking-horse" {...props}></Icon>
