<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq92k6g1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq92k6g1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:down-2" {...props}></Icon>
