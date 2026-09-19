<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klzv45b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="klzv45b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:edit" {...props}></Icon>
