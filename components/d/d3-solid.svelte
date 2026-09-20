<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-k6kc-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="x-k6kc-pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:d3-solid" {...props}></Icon>
