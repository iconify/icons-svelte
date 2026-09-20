<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr0aked4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rr0aked4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:mail" {...props}></Icon>
