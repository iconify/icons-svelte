<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yntco8syx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yntco8syx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear" {...props}></Icon>
