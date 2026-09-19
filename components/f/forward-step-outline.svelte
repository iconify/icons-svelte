<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgjgk_8pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgjgk_8pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:forward-step-outline" {...props}></Icon>
