<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a89o3fw4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a89o3fw4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:js-square" {...props}></Icon>
