<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8uxgbcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r8uxgbcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-top-right" {...props}></Icon>
