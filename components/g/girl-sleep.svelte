<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevs3izuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uevs3izuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-sleep" {...props}></Icon>
