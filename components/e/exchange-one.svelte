<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r037uibrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r037uibrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:exchange-one" {...props}></Icon>
