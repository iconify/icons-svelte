<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5nqjs1-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t5nqjs1-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-legged-octopus" {...props}></Icon>
