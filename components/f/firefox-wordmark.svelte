<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-opoeb5s.css';
import '../../css/k/k4cnuob7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="m-opoeb5s"/><path class="k4cnuob7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:firefox-wordmark" {...props}></Icon>
