<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa-h57bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xa-h57bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-square-outline" {...props}></Icon>
