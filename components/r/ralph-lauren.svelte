<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iihrjxbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":684,"height":1568};
const content = `<path class="iihrjxbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ralph-lauren" {...props}></Icon>
