<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x81pse-8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x81pse-8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:npm-solid" {...props}></Icon>
