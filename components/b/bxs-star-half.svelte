<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9i0xrbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9i0xrbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-star-half" {...props}></Icon>
