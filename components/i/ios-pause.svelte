<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt6oa8btc.css';
import '../../css/n/n2b3ufqkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vt6oa8btc"/><path class="n2b3ufqkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pause" {...props}></Icon>
