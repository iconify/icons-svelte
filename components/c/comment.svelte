<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivn7p0b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ivn7p0b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:comment" {...props}></Icon>
