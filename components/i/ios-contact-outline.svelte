<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-g5_2e4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-g5_2e4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-contact-outline" {...props}></Icon>
