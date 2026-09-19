<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njjyxzbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njjyxzbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ordered-list-outline" {...props}></Icon>
