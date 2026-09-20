<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geair-clw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="geair-clw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:minus-circle" {...props}></Icon>
