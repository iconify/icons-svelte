<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21-q0eyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z21-q0eyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:micro-sd" {...props}></Icon>
