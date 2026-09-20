<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6-sa7uud.css';
import '../../css/a/a_ygf-j1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m6-sa7uud"/><path class="a_ygf-j1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lightning-cable-solid" {...props}></Icon>
