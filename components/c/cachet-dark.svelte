<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwyj592ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwyj592ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cachet-dark" {...props}></Icon>
