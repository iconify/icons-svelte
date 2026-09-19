<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwq3qbwrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwq3qbwrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:between-vertical-start" {...props}></Icon>
