<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg2jepl7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gg2jepl7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:barber-brush" {...props}></Icon>
