<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c39hpngvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c39hpngvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:plus" {...props}></Icon>
