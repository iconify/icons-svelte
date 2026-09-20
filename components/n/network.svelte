<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agzafq8wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="agzafq8wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:network" {...props}></Icon>
