<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sasqfv1ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sasqfv1ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:farm" {...props}></Icon>
