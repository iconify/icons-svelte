<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg0cz-ynl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg0cz-ynl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:check-solid" {...props}></Icon>
