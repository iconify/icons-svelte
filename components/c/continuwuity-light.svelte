<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elzab8bky.css';
import '../../css/f/funyg-b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elzab8bky"/><path class="funyg-b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:continuwuity-light" {...props}></Icon>
