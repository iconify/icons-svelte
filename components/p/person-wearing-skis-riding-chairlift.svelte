<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1n_3d2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lm1n_3d2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-skis-riding-chairlift" {...props}></Icon>
