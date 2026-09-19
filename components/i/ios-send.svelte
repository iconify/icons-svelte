<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iygfuccbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iygfuccbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-send" {...props}></Icon>
