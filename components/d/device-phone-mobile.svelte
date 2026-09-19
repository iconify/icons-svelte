<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqcp8bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqqcp8bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:device-phone-mobile" {...props}></Icon>
