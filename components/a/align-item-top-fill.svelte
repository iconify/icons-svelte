<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihq9t13ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihq9t13ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-top-fill" {...props}></Icon>
