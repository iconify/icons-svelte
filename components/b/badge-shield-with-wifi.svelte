<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmiss0b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jmiss0b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badge-shield-with-wifi" {...props}></Icon>
