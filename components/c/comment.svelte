<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nclm2o22a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="nclm2o22a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:comment" {...props}></Icon>
