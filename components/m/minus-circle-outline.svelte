<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh2gx_b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eh2gx_b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:minus-circle-outline" {...props}></Icon>
