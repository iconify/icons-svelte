<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3jht4bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3jht4bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:globe-stroke-20" {...props}></Icon>
