<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt7o7dq2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt7o7dq2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-dot" {...props}></Icon>
