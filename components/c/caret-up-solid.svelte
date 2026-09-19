<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewulr6ukt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewulr6ukt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-up-solid" {...props}></Icon>
