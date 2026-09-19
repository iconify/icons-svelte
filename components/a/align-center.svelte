<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9o6lfw2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="c9o6lfw2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:align-center" {...props}></Icon>
