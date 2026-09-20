<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3p8uubfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3p8uubfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:circle-notch-solid" {...props}></Icon>
