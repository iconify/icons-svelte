<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_n6nb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_n6nb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paintbrush-vertical-filled" {...props}></Icon>
