<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5r6won4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k5r6won4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paintbrush-outline" {...props}></Icon>
