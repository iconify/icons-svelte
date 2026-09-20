<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ywfrbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1ywfrbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-objects-vertically" {...props}></Icon>
