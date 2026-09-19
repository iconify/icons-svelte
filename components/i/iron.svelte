<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0kgj6bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0kgj6bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:iron" {...props}></Icon>
