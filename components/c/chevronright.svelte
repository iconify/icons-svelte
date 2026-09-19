<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbvq0z1dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="rbvq0z1dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chevronright" {...props}></Icon>
