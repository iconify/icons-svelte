<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3lxxbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp3lxxbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:navigate-sharp" {...props}></Icon>
