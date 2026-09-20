<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_914pbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="g_914pbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:battle-axe" {...props}></Icon>
