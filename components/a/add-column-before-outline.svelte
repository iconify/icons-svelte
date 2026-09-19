<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c66ev-hat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c66ev-hat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:add-column-before-outline" {...props}></Icon>
