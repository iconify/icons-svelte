<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvr-94mbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="wvr-94mbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phpmyfaq" {...props}></Icon>
