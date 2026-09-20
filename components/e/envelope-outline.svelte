<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_g6s6b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y_g6s6b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:envelope-outline" {...props}></Icon>
