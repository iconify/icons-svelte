<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj0z13bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj0z13bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:carrot-solid" {...props}></Icon>
