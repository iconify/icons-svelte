<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c85z90qgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c85z90qgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minuspod-dark" {...props}></Icon>
