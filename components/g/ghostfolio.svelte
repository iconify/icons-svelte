<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwcuq-bwx.css';
import '../../css/d/dcwqgdbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwcuq-bwx"/><path class="dcwqgdbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostfolio" {...props}></Icon>
