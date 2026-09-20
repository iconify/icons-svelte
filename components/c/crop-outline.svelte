<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj7ykkl-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nj7ykkl-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:crop-outline" {...props}></Icon>
