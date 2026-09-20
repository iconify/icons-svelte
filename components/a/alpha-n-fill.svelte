<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bosfi5b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bosfi5b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-n-fill" {...props}></Icon>
