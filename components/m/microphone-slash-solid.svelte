<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtiocmbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtiocmbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:microphone-slash-solid" {...props}></Icon>
