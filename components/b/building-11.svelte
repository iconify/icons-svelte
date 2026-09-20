<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hts6zhr3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hts6zhr3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:building-11" {...props}></Icon>
