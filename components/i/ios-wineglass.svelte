<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5kq0zb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5kq0zb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-wineglass" {...props}></Icon>
