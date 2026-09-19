<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wemmq4bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wemmq4bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:filter-sharp" {...props}></Icon>
