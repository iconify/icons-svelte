<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmtassnnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmtassnnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaticle-dark" {...props}></Icon>
