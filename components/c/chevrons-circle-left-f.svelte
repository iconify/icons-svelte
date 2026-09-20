<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc5jrr1xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="pc5jrr1xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-left-f" {...props}></Icon>
