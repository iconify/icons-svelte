<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7yn_-5rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7yn_-5rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:electronics-transister" {...props}></Icon>
