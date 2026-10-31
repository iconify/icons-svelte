<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8a4hlb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8a4hlb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-m" {...props}></Icon>
