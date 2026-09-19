<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx7ghw7nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jx7ghw7nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arrow-left" {...props}></Icon>
