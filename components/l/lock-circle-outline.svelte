<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulp9kbc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ulp9kbc7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lock-circle-outline" {...props}></Icon>
