<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycdk8iqtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":984.7,"height":175.5};
const content = `<path class="ycdk8iqtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hymer" {...props}></Icon>
