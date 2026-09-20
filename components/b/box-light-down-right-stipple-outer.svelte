<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk9lr3b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gk9lr3b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-right-stipple-outer" {...props}></Icon>
