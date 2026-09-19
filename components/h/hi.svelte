<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4ambcacz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o4ambcacz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hi" {...props}></Icon>
