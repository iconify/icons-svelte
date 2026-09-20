<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykg-_fbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ykg-_fbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-ix" {...props}></Icon>
