<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyq8pmbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyq8pmbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-4-line" {...props}></Icon>
