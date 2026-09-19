<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eik3fo4xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eik3fo4xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bottle-one" {...props}></Icon>
