<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fio84ly5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fio84ly5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-right-outline" {...props}></Icon>
