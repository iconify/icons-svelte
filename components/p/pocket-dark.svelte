<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjjjqcbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjjjqcbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-dark" {...props}></Icon>
