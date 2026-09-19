<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhe79hh6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qhe79hh6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right" {...props}></Icon>
