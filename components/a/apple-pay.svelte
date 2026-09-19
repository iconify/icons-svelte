<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ass-29u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="c8ass-29u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:apple-pay" {...props}></Icon>
