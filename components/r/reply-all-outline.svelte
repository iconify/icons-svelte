<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx06klr2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx06klr2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:reply-all-outline" {...props}></Icon>
