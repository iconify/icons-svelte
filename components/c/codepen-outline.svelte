<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2wxxeb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h2wxxeb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:codepen-outline" {...props}></Icon>
