<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apdg82bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="apdg82bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-solid" {...props}></Icon>
