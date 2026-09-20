<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf5_hobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf5_hobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitchenowl-light" {...props}></Icon>
