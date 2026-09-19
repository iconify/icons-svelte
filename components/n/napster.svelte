<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l64tr8bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="l64tr8bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:napster" {...props}></Icon>
