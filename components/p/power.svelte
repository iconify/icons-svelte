<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5v46b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="od5v46b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:power" {...props}></Icon>
