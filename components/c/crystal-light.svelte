<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7qd0xhrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":200};
const content = `<path class="k7qd0xhrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:crystal-light" {...props}></Icon>
