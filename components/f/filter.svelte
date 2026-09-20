<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqfi6ubqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gqfi6ubqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:filter" {...props}></Icon>
