<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3q4aactz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q3q4aactz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:menu-up-down" {...props}></Icon>
