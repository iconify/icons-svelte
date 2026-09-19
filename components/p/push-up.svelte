<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxwgl5-1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxwgl5-1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:push-up" {...props}></Icon>
