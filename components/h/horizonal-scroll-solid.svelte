<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbd61esfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bbd61esfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:horizonal-scroll-solid" {...props}></Icon>
