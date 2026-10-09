<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aizeie9_j.css';
import '../../css/d/d-a358n2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aizeie9_j"/><path class="d-a358n2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:picnic-20" {...props}></Icon>
