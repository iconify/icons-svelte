<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrfw7f0oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrfw7f0oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-multiple-minus" {...props}></Icon>
