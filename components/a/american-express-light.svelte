<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq-edkbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zq-edkbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-express-light" {...props}></Icon>
