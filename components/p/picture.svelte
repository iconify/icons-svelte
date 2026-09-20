<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dplvd83tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dplvd83tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:picture" {...props}></Icon>
