<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu4mlnbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mu4mlnbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-peace" {...props}></Icon>
