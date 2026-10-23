<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khyu9dbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khyu9dbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-warning" {...props}></Icon>
