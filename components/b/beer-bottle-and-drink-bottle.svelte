<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg7ocnbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hg7ocnbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:beer-bottle-and-drink-bottle" {...props}></Icon>
