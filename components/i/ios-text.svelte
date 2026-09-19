<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb8hxx_up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zb8hxx_up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-text" {...props}></Icon>
