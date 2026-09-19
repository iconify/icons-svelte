<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7wky1pgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7wky1pgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:moodbubble" {...props}></Icon>
