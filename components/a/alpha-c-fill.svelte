<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih7wd8-4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ih7wd8-4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-c-fill" {...props}></Icon>
