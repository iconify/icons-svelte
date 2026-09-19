<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgaiz9bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pgaiz9bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-right-two" {...props}></Icon>
