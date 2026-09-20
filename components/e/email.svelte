<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdbwkzbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wdbwkzbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:email" {...props}></Icon>
