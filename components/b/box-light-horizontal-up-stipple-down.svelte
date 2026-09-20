<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa2ueoszy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oa2ueoszy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up-stipple-down" {...props}></Icon>
