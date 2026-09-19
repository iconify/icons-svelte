<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_kw9bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xs_kw9bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:hexagon-strip" {...props}></Icon>
