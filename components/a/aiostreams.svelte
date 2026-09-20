<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqe80svqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqe80svqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiostreams" {...props}></Icon>
