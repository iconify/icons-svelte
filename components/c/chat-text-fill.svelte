<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u-odb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n5u-odb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-text-fill" {...props}></Icon>
