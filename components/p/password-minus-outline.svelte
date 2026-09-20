<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9t50ung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9t50ung"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:password-minus-outline" {...props}></Icon>
