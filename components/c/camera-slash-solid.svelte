<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_ao0-bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ao0-bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:camera-slash-solid" {...props}></Icon>
