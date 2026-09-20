<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chsjt2b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="chsjt2b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paragraph-outline" {...props}></Icon>
