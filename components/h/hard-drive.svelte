<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8hninb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="p8hninb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hard-drive" {...props}></Icon>
