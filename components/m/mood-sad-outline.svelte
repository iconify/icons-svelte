<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtt0f29xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mtt0f29xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-sad-outline" {...props}></Icon>
