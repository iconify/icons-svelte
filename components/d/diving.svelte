<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa0e86bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xa0e86bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diving" {...props}></Icon>
