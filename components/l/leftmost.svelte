<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3_3rlbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g3_3rlbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:leftmost" {...props}></Icon>
