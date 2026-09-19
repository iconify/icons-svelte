<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5_j0fbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g5_j0fbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-up-box-fill-12" {...props}></Icon>
