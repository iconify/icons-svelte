<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut34iny4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ut34iny4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adguard-home-light" {...props}></Icon>
