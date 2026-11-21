<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhur_sbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhur_sbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codetta-light" {...props}></Icon>
