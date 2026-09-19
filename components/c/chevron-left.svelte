<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5y8o05ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5y8o05ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:chevron-left" {...props}></Icon>
