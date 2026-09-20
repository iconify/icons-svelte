<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjp9ywjxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjp9ywjxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:lock-open-alt" {...props}></Icon>
