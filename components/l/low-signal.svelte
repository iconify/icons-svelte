<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thluib7ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thluib7ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:low-signal" {...props}></Icon>
