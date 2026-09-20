<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzfyu8bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jzfyu8bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-u-fill" {...props}></Icon>
