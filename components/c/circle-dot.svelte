<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w14ec4bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w14ec4bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-dot" {...props}></Icon>
