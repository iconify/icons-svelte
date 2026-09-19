<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qksbz5ces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qksbz5ces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:envelope-outline" {...props}></Icon>
