<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-6_f9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-6_f9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-x-fill" {...props}></Icon>
