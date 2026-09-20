<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9u7-kb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9u7-kb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pent-no-dark" {...props}></Icon>
