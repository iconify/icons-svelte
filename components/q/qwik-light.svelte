<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_2ocb6i.css';
import '../../css/o/o9yvq7pij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1_2ocb6i"/><path class="o9yvq7pij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qwik-light" {...props}></Icon>
