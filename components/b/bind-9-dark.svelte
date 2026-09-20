<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxc3l3bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc3l3bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bind-9-dark" {...props}></Icon>
