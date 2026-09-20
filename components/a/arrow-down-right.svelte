<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymkz3sb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ymkz3sb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-right" {...props}></Icon>
