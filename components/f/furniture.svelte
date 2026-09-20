<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn49wrlsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nn49wrlsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:furniture" {...props}></Icon>
