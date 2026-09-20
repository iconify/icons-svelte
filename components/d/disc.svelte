<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a37j-kbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="a37j-kbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:disc" {...props}></Icon>
