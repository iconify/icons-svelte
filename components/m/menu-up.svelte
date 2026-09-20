<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gid6_9bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gid6_9bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:menu-up" {...props}></Icon>
