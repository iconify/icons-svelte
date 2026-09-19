<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl3x9zbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":480};
const content = `<path class="nl3x9zbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:link" {...props}></Icon>
