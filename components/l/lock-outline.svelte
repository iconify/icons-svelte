<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyf8j3bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyf8j3bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lock-outline" {...props}></Icon>
