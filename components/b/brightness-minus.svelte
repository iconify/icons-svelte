<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3hvndbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3hvndbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:brightness-minus" {...props}></Icon>
