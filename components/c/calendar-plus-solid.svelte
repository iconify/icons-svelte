<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru4zkgb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru4zkgb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:calendar-plus-solid" {...props}></Icon>
