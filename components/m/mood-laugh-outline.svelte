<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3o1lpb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b3o1lpb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-laugh-outline" {...props}></Icon>
