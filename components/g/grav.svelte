<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3bqw9bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o3bqw9bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:grav" {...props}></Icon>
