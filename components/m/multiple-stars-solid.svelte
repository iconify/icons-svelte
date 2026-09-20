<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wblctf01d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wblctf01d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:multiple-stars-solid" {...props}></Icon>
