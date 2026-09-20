<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1u5wbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii1u5wbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextdoor-light" {...props}></Icon>
