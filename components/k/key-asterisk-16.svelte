<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se52wg45h.css';
import '../../css/c/c38uaibrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="se52wg45h"/><path class="c38uaibrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:key-asterisk-16" {...props}></Icon>
