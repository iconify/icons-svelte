<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyhd5yy6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyhd5yy6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:calendar-plus-outline" {...props}></Icon>
