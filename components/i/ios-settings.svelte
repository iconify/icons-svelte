<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8by7gb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8by7gb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-settings" {...props}></Icon>
