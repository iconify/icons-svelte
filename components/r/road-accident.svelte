<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7656tb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n7656tb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:road-accident" {...props}></Icon>
