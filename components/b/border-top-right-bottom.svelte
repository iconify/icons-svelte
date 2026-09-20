<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkte9o6es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rkte9o6es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top-right-bottom" {...props}></Icon>
