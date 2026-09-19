<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctjmp2b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctjmp2b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloudy-outline" {...props}></Icon>
