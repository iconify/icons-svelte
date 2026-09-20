<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7rvp3y7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7rvp3y7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-outline" {...props}></Icon>
