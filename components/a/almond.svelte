<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhmkg2bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fhmkg2bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:almond" {...props}></Icon>
