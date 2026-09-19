<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed19s4bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ed19s4bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:glass-martini-alt" {...props}></Icon>
